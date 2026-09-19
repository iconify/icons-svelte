<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2so5n4so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2so5n4so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:shield-check-outline" {...props}></Icon>
