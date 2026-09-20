<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eidqzhvmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eidqzhvmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:view-grid" {...props}></Icon>
