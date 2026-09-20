<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-pz3ub-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-pz3ub-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:table-24" {...props}></Icon>
