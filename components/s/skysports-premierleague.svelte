<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg61nuzkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg61nuzkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:skysports-premierleague" {...props}></Icon>
