<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyndy7y0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dyndy7y0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:umbrella" {...props}></Icon>
