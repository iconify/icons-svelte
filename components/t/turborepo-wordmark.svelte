<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_zymqb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="m_zymqb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:turborepo-wordmark" {...props}></Icon>
