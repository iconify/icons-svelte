<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quv0rgtyg.css';
import '../../css/h/hgxtv_kog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="quv0rgtyg"/><path class="hgxtv_kog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:speaker-1-16" {...props}></Icon>
