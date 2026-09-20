<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i332-pb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i332-pb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sort-asc-24" {...props}></Icon>
