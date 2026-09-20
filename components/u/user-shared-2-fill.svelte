<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4xl89bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4xl89bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-shared-2-fill" {...props}></Icon>
