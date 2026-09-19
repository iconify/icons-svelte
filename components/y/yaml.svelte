<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehev_nbyn.css';
import '../../css/l/l028m6bye.css';
import '../../css/f/fr-8w9hqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ehev_nbyn"/><path class="l028m6bye"/><path class="fr-8w9hqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:yaml" {...props}></Icon>
