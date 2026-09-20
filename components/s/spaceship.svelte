<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo25cncdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo25cncdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:spaceship" {...props}></Icon>
