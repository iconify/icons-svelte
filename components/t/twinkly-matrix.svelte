<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh9lccczm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uh9lccczm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:twinkly-matrix" {...props}></Icon>
