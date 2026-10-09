<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyzjbf5oz.css';
import '../../css/b/bs8u9-bib.css';
import '../../css/d/dz2xsntoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zyzjbf5oz"/><path class="bs8u9-bib"/><path class="dz2xsntoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-48" {...props}></Icon>
