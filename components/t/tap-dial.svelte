<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug334vb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug334vb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tap-dial" {...props}></Icon>
