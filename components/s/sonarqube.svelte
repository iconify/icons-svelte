<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3qb-qbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g3qb-qbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:sonarqube" {...props}></Icon>
