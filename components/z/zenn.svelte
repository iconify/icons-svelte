<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mej-j8b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mej-j8b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zenn" {...props}></Icon>
