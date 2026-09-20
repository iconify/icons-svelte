<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag0ok82cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag0ok82cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:ungroup" {...props}></Icon>
