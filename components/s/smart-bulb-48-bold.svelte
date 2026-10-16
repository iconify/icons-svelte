<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0m3wcb9a.css';
import '../../css/e/e72pk-7vm.css';
import '../../css/b/bowjjxblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u0m3wcb9a"/><path class="e72pk-7vm"/><path class="bowjjxblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-bulb-48-bold" {...props}></Icon>
