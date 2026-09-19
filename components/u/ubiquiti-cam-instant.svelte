<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syl817pyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="syl817pyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubiquiti-cam-instant" {...props}></Icon>
