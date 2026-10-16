<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zen2agbyu.css';
import '../../css/z/zaedueqlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zen2agbyu"/><path class="zaedueqlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-round-48" {...props}></Icon>
