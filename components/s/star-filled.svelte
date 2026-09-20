<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8-d7z.css';
import '../../css/m/mnwdzw.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-34.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8-d7z"/><path class="mnwdzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-filled" {...props}></Icon>
