<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m41mmzbsh.css';
import '../../css/a/a922yib7w.css';
import '../../css/u/ulfe3ccxn.css';
import '../../css/t/t99_mr0an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m41mmzbsh"/><path class="a922yib7w"/><path class="ulfe3ccxn"/><path class="t99_mr0an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:suitcase-bold-duotone" {...props}></Icon>
