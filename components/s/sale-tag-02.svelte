<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jloxq3b0a.css';
import '../../css/t/t01qni1jx.css';
import '../../css/t/ttry_thll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jloxq3b0a"/><path class="t01qni1jx"/><path class="ttry_thll"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:sale-tag-02" {...props}></Icon>
