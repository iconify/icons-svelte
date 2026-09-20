<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgiiglbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgiiglbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:suitcase-3-fill" {...props}></Icon>
