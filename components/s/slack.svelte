<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6r28jcem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6r28jcem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:slack" {...props}></Icon>
