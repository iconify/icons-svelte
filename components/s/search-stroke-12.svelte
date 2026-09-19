<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbb1_2bju.css';
import '../../css/w/w43j2ubna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="nbb1_2bju"/><path class="w43j2ubna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:search-stroke-12" {...props}></Icon>
