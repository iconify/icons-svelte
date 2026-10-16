<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa8mtjico.css';
import '../../css/h/hzl2uybek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pa8mtjico"/><path class="hzl2uybek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:silicon-48" {...props}></Icon>
