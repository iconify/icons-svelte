<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb7672bzg.css';
import '../../css/e/eyk4iwcnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb7672bzg"/><path class="eyk4iwcnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vee" {...props}></Icon>
