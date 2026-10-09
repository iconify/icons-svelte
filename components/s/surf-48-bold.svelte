<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu6ys3bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nu6ys3bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:surf-48-bold" {...props}></Icon>
