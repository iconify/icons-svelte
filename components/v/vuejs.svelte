<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvf8mrwdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvf8mrwdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:vuejs" {...props}></Icon>
