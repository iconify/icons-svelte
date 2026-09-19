<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttn-_-n5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1932,"height":701};
const content = `<path class="ttn-_-n5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:sqale" {...props}></Icon>
