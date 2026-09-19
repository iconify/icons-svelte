<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuu1fpbjf.css';
import '../../css/r/rkquswc8h.css';
import '../../css/l/l8bnbhbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xuu1fpbjf"/><path class="rkquswc8h"/><path clip-rule="evenodd" class="l8bnbhbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:user-clock-outline" {...props}></Icon>
