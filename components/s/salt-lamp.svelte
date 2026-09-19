<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1r6vzg8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1r6vzg8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:salt-lamp" {...props}></Icon>
