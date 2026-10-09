<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml6m6q55w.css';
import '../../css/y/ybtkb5jlq.css';
import '../../css/o/o9f6xfbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ml6m6q55w"/><path class="ybtkb5jlq"/><path class="o9f6xfbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:washer-48-bold" {...props}></Icon>
