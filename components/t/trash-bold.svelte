<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlp2jsb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlp2jsb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:trash-bold" {...props}></Icon>
