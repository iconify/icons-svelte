<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_93pgbru.css';
import '../../css/r/ra-4wynoj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_93pgbru"/><path class="ra-4wynoj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:sign-out-alt-fill" {...props}></Icon>
