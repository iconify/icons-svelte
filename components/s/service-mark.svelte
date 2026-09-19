<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynhhlqb6o.css';
import '../../css/j/jbls2nr5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ynhhlqb6o"/><path class="jbls2nr5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:service-mark" {...props}></Icon>
