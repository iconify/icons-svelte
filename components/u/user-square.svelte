<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scmm0jbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scmm0jbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:user-square" {...props}></Icon>
