<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgdcovbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgdcovbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zodiac-capricorn" {...props}></Icon>
