<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui6oo4bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui6oo4bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:zoom-out-outline" {...props}></Icon>
