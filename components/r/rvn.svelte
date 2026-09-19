<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df1gw3ghw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df1gw3ghw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rvn" {...props}></Icon>
