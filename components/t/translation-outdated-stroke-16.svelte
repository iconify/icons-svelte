<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxk486bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zxk486bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-outdated-stroke-16" {...props}></Icon>
