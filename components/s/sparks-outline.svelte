<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm0tk8bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sparks-outline"><path class="Vector gm0tk8bew" clip-rule="evenodd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:sparks-outline" {...props}></Icon>
