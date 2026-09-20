<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmjhp2sbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmjhp2sbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:wifi-slash-expressive" {...props}></Icon>
