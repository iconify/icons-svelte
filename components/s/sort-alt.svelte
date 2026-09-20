<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da74jmbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="da74jmbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:sort-alt" {...props}></Icon>
