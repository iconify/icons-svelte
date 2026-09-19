<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bto0-4bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bto0-4bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:uk-scouts" {...props}></Icon>
