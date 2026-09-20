<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3-5_c46r.css';
import '../../css/f/fgtzzk1mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3-5_c46r"/><path class="fgtzzk1mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wagmigames" {...props}></Icon>
