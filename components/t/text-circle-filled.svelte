<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izbfeq86f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="izbfeq86f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:text-circle-filled" {...props}></Icon>
