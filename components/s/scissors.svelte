<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q87ez3nph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q87ez3nph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scissors" {...props}></Icon>
