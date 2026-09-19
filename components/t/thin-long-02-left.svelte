<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1po4kbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1po4kbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:thin-long-02-left" {...props}></Icon>
