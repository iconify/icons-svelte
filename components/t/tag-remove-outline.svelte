<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to542-bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to542-bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-remove-outline" {...props}></Icon>
