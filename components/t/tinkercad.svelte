<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_-d-b5tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_-d-b5tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tinkercad" {...props}></Icon>
