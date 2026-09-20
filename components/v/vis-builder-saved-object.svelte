<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8s6xvu0y.css';
import '../../css/v/v-nzisfqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w8s6xvu0y"/><path class="v-nzisfqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-builder-saved-object" {...props}></Icon>
