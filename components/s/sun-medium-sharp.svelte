<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unb5jhb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unb5jhb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sun-medium-sharp" {...props}></Icon>
