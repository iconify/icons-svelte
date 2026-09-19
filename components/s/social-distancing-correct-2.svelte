<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz1whib-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qz1whib-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:social-distancing-correct-2" {...props}></Icon>
