<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-6j15bmw.css';
import '../../css/w/w96tcbb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-6j15bmw"/><path class="w96tcbb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:time-clock-circle" {...props}></Icon>
