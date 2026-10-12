<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1p6d7jyb.css';
import '../../css/x/xiad0yblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1p6d7jyb"/><path class="xiad0yblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:text-cursor-input-filled" {...props}></Icon>
