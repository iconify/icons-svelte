<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzyze9cmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzyze9cmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rows-four-filled" {...props}></Icon>
