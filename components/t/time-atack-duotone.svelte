<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvsj4rbkk.css';
import '../../css/f/f42ipub-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="yvsj4rbkk"/><path class="f42ipub-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:time-atack-duotone" {...props}></Icon>
