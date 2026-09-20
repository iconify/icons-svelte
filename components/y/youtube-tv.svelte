<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oji7_mciu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oji7_mciu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:youtube-tv" {...props}></Icon>
