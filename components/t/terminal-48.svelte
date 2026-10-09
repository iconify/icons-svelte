<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9weu6t_z.css';
import '../../css/l/li0btfuqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e9weu6t_z"/><path class="li0btfuqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:terminal-48" {...props}></Icon>
