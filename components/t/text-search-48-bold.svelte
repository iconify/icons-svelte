<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4aitobkj.css';
import '../../css/w/w33pk5bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n4aitobkj"/><path class="w33pk5bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-search-48-bold" {...props}></Icon>
