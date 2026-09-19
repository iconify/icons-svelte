<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5wleyipv.css';
import '../../css/u/uxlky7uhp.css';
import '../../css/c/cq11jcb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n5wleyipv"/><path class="uxlky7uhp"/><path class="cq11jcb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sonarqube-wordmark" {...props}></Icon>
