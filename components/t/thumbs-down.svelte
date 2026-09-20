<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/ga_sunbve.css';
import '../../css/v/v9_s8abew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect transform="rotate(180 21.25 16.8)" class="ga_sunbve"/><path class="v9_s8abew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:thumbs-down" {...props}></Icon>
