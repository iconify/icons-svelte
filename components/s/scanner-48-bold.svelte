<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnv4p6ezk.css';
import '../../css/o/orzcsyqzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bnv4p6ezk"/><path class="orzcsyqzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scanner-48-bold" {...props}></Icon>
