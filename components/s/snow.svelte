<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq-5_4bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hq-5_4bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:snow" {...props}></Icon>
