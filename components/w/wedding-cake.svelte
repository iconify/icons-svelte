<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eest8db3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="eest8db3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:wedding-cake" {...props}></Icon>
