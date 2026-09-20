<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw2xxxbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xw2xxxbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ted-logo-solid" {...props}></Icon>
