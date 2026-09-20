<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr9ub67zs.css';
import '../../css/l/lrrff2bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr9ub67zs"/><path class="lrrff2bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:signin" {...props}></Icon>
