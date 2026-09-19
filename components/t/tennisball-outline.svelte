<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnii4hccr.css';
import '../../css/f/f345gcb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="rnii4hccr"/><path class="f345gcb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:tennisball-outline" {...props}></Icon>
