<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udkqglw3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="udkqglw3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:scp" {...props}></Icon>
