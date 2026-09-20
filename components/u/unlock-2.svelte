<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t48va3bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="t48va3bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:unlock-2" {...props}></Icon>
