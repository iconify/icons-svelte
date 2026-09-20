<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr0ysc8zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr0ysc8zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-remove-outline" {...props}></Icon>
