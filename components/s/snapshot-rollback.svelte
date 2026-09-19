<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcus66bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcus66bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:snapshot-rollback" {...props}></Icon>
