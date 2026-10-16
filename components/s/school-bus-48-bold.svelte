<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwgm7fbxw.css';
import '../../css/c/cdyatobkg.css';
import '../../css/z/zcwxudbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bwgm7fbxw"/><path class="cdyatobkg"/><path class="zcwxudbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:school-bus-48-bold" {...props}></Icon>
