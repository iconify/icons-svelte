<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-msclb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-msclb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:siren" {...props}></Icon>
