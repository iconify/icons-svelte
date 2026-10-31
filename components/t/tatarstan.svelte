<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukv6olbwm.css';
import '../../css/f/fnblp6ymy.css';
import '../../css/j/jcc8b939g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="ukv6olbwm"/><path class="fnblp6ymy"/><path class="jcc8b939g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:tatarstan" {...props}></Icon>
