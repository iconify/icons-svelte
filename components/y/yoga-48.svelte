<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeaj4ri2b.css';
import '../../css/x/xn9gzsb0y.css';
import '../../css/h/hlj3itbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zeaj4ri2b"/><path class="xn9gzsb0y"/><path class="hlj3itbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:yoga-48" {...props}></Icon>
