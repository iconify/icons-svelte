<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paykg7zgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paykg7zgg primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:swimmer-duotone" {...props}></Icon>
