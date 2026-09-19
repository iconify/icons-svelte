<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slf5fkzrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="slf5fkzrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:sonarqube-wordmark" {...props}></Icon>
