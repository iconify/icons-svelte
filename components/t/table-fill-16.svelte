<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjbvnem1g.css';
import '../../css/p/ppiwk-bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="qjbvnem1g"/><path class="ppiwk-bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:table-fill-16" {...props}></Icon>
