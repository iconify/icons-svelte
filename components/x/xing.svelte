<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9k3qibgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9k3qibgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xing" {...props}></Icon>
