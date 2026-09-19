<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_5qzjm2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_5qzjm2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-bridge" {...props}></Icon>
