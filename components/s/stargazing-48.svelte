<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blpec2f_v.css';
import '../../css/p/pwrb__blp.css';
import '../../css/g/g1qd2ab1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="blpec2f_v"/><path class="pwrb__blp"/><path class="g1qd2ab1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stargazing-48" {...props}></Icon>
