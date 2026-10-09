<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8kv1hbar.css';
import '../../css/g/gb_71gb0y.css';
import '../../css/y/yvuobzjdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j8kv1hbar"/><path class="gb_71gb0y"/><path class="yvuobzjdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermometer-up-48-bold" {...props}></Icon>
