<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5snn3b0a.css';
import '../../css/e/ek3qulhkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e5snn3b0a"/><path clip-rule="evenodd" class="ek3qulhkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-time-desc-16" {...props}></Icon>
