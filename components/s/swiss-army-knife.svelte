<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd8oh8xxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="vd8oh8xxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:swiss-army-knife" {...props}></Icon>
