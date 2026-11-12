<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgt426vre.css';
import '../../css/n/n9h5yebjh.css';
import '../../css/k/k_lrs8b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hgt426vre"/><path class="n9h5yebjh"/><path class="k_lrs8b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:steamgriddb-dark" {...props}></Icon>
