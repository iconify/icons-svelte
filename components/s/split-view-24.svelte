<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-1u-rbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-1u-rbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:split-view-24" {...props}></Icon>
