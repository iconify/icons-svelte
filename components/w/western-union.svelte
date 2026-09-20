<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlix1cbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlix1cbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:western-union" {...props}></Icon>
