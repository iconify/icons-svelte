<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrs4mmk_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rrs4mmk_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:speaker" {...props}></Icon>
