<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck-mwvbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-mwvbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:telescope-fill-24" {...props}></Icon>
