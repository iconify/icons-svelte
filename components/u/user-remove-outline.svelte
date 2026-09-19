<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlsvvd75m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlsvvd75m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:user-remove-outline" {...props}></Icon>
