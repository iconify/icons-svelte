<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb37wj2kt.css';
import '../../css/k/k8xftibiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="cb37wj2kt"/><path class="k8xftibiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:statistic-map" {...props}></Icon>
