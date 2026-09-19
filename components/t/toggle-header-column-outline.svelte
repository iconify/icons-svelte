<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpyti5o6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpyti5o6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:toggle-header-column-outline" {...props}></Icon>
