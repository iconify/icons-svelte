<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adswyhb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="adswyhb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sun-48-bold" {...props}></Icon>
