<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ski0eqc8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ski0eqc8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:semver" {...props}></Icon>
