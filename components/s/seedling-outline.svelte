<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-3iuhfng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-3iuhfng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:seedling-outline" {...props}></Icon>
