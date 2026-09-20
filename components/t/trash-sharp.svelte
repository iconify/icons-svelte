<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8mi811tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8mi811tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:trash-sharp" {...props}></Icon>
