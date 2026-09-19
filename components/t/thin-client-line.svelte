<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzv_u_b-g.css';
import '../../css/n/noehlf0bk.css';
import '../../css/f/fk0yjerem.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="nzv_u_b-g"/><circle class="noehlf0bk"/><path class="fk0yjerem"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:thin-client-line" {...props}></Icon>
