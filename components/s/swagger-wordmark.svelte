<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9skdhbhr.css';
import '../../css/m/mg5nb2b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q9skdhbhr"/><path class="mg5nb2b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:swagger-wordmark" {...props}></Icon>
