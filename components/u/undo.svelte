<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk-762bui.css';
import '../../css/x/xi6rm2m0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="zk-762bui"/><path class="xi6rm2m0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:undo" {...props}></Icon>
