<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iph2hoksm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iph2hoksm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:widget-alt-1-line" {...props}></Icon>
