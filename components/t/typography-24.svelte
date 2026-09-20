<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot7u5ufdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot7u5ufdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:typography-24" {...props}></Icon>
