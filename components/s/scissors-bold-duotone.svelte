<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtjjt6bok.css';
import '../../css/v/v-e0rbmkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtjjt6bok"/><path class="v-e0rbmkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:scissors-bold-duotone" {...props}></Icon>
