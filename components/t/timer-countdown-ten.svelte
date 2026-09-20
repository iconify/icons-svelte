<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdnqinu8h.css';
import '../../css/h/hmnz6jb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdnqinu8h"/><path class="hmnz6jb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:timer-countdown-ten" {...props}></Icon>
