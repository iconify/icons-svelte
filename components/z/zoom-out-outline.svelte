<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3wh155go.css';
import '../../css/i/i_8ytb8-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3wh155go"/><path clip-rule="evenodd" class="i_8ytb8-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:zoom-out-outline" {...props}></Icon>
