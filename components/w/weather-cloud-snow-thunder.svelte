<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/goerp7bib.css';
import '../../css/j/j5nhi9bbx.css';
import '../../css/h/hfnzlwbvs.css';
import '../../css/y/yq7deobye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="goerp7bib"/><path class="j5nhi9bbx"/><path class="hfnzlwbvs"/><path class="yq7deobye"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:weather-cloud-snow-thunder" {...props}></Icon>
