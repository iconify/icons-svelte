<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9j5b1edd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9j5b1edd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:scrutinizer-ci" {...props}></Icon>
