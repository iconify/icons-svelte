<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiqfwabog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uiqfwabog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ticket" {...props}></Icon>
